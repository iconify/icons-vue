<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ksa64jblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ksa64jblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-2x2-solid" /></template>
