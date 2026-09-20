<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hrv6hs_bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hrv6hs_bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:file-bookmark-alt" /></template>
