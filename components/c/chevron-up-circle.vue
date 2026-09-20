<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g4zs08s-q.css';
import '../../css/k/kacv-xbnn.css';
import '../../css/p/p9tgkebiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g4zs08s-q"/><path class="kacv-xbnn"/><path class="p9tgkebiq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:chevron-up-circle" /></template>
