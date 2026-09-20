<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh336ri0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh336ri0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gender-genderless" /></template>
