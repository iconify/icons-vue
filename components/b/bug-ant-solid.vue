<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/robgy6qcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="robgy6qcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:bug-ant-solid" /></template>
