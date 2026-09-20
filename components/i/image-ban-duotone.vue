<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxa465p2f.css';
import '../../css/i/iz8c3l5-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxa465p2f"/><path class="iz8c3l5-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-ban-duotone" /></template>
