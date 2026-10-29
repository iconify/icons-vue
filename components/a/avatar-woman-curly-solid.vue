<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v73kcqc0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v73kcqc0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-woman-curly-solid" /></template>
