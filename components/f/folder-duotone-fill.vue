<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf5a1pvvg.css';
import '../../css/k/kgk49pb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf5a1pvvg"/><path class="kgk49pb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:folder-duotone-fill" /></template>
