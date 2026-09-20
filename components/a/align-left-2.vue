<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1tt42brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1tt42brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-left-2" /></template>
