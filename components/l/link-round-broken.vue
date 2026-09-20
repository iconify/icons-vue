<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-ofhyb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-ofhyb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-round-broken" /></template>
