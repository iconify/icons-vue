<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqng2_39f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqng2_39f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:location-reduction-filled" /></template>
