<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y64ctubyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y64ctubyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:exposure-0" /></template>
