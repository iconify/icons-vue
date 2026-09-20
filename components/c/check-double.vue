<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnbsg9ofn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnbsg9ofn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:check-double" /></template>
