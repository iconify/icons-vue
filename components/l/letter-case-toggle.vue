<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4hcemb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4hcemb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-case-toggle" /></template>
