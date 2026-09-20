<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv10nottr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv10nottr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:file-phone-filled" /></template>
