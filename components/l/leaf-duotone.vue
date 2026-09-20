<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de1zgmdha.css';
import '../../css/j/jloulibzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de1zgmdha"/><path clip-rule="evenodd" class="jloulibzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:leaf-duotone" /></template>
