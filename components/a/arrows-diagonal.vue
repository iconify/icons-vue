<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8utjoj0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o8utjoj0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-diagonal" /></template>
