<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3peti11w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q3peti11w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:eye-slash" /></template>
