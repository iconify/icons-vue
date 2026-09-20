<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln_2etbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln_2etbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:airpods-open-fill" /></template>
