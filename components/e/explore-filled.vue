<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_7prvx0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_7prvx0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:explore-filled" /></template>
