<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm95fc3hw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm95fc3hw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:exposure" /></template>
