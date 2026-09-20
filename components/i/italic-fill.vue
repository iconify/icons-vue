<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpa6-tfum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpa6-tfum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:italic-fill" /></template>
