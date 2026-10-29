<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh2c-ku4e.css';
import '../../css/d/d-fe0zkrl.css';
import '../../css/m/mvvzj2tgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mh2c-ku4e wm-shadow"/><path class="d-fe0zkrl wm-k"/><path class="mvvzj2tgs wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:align-left" /></template>
