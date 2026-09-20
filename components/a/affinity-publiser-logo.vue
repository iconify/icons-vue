<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gko5h7otm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gko5h7otm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:affinity-publiser-logo" /></template>
