<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qq8xb2ljf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qq8xb2ljf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:bug-light" /></template>
