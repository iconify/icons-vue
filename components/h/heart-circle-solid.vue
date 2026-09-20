<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9qr0pwdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="a9qr0pwdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:heart-circle-solid" /></template>
