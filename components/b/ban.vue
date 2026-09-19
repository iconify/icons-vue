<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1t0lfkdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1t0lfkdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:ban" /></template>
