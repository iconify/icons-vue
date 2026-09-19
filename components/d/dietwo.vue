<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3bd7mocx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":959};
const content = `<path class="k3bd7mocx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dietwo" /></template>
