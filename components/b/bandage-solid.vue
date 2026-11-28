<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0ecwab0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0ecwab0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:bandage-solid" /></template>
