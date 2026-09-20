<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lob-de45c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lob-de45c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-l-small" /></template>
