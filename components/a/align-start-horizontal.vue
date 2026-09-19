<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gb77abcux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gb77abcux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:align-start-horizontal" /></template>
