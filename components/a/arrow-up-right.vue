<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh3ha2b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh3ha2b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-up-right" /></template>
