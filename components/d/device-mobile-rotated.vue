<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pwzk46bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwzk46bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-mobile-rotated" /></template>
