<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koo-gmb4d.css';
import '../../css/h/h1-_tjb6i.css';
import '../../css/r/r68kisbcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koo-gmb4d wm-shadow"/><path class="h1-_tjb6i wm-k"/><path class="r68kisbcu wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:align-justify" /></template>
