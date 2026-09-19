<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2nvl-0be.css';
import '../../css/l/lt7jyeb_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2nvl-0be"/><path class="lt7jyeb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bacteria" /></template>
