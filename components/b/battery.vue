<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt04zybco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt04zybco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:battery" /></template>
