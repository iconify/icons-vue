<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euuo8mlxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="euuo8mlxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fileflows-dark" /></template>
