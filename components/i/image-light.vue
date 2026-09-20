<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi2419bxd.css';
import '../../css/h/hcenjub2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi2419bxd"/><path class="hcenjub2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-light" /></template>
