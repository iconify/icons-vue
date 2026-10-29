<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r72qw3b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r72qw3b9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-bear-solid" /></template>
