<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jueal6bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jueal6bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-to-top-right-broken" /></template>
