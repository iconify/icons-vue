<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efrn45bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efrn45bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-minus-sharp" /></template>
