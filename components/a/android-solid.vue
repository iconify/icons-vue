<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym_r_5nav.css';
import '../../css/o/o7sf9lkhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym_r_5nav"/><path class="o7sf9lkhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:android-solid" /></template>
