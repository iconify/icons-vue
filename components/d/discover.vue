<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfo1k5b-e.css';
import '../../css/i/iqt8i0b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":14};
const content = `<path class="sfo1k5b-e"/><path class="iqt8i0b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:discover" /></template>
