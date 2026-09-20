<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcxd1c7pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kcxd1c7pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:exposure-plus-2" /></template>
