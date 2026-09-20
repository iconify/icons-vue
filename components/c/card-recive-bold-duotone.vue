<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4-q_acah.css';
import '../../css/r/rve9bjm7q.css';
import '../../css/g/gvic217pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4-q_acah"/><path clip-rule="evenodd" class="rve9bjm7q"/><path class="gvic217pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:card-recive-bold-duotone" /></template>
