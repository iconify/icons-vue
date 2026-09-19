<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn3lrh4wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn3lrh4wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:lock-open-solid" /></template>
