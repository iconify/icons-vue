<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw6i4cczk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qw6i4cczk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:bug" /></template>
