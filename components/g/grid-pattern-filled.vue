<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ng999dbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng999dbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:grid-pattern-filled" /></template>
