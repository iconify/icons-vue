<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eslqwkb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eslqwkb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:laurel-wreath-1-filled" /></template>
