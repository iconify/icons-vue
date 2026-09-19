<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdd82p7ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdd82p7ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:fortress" /></template>
