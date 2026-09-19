<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thuxc19tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":897,"height":1024};
const content = `<path class="thuxc19tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:christmasstree" /></template>
