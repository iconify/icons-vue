<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qi52v6bpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qi52v6bpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-to-bottom" /></template>
