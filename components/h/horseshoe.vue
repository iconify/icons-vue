<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f61c29bkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f61c29bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:horseshoe" /></template>
