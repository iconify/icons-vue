<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npk_kkbww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="npk_kkbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bitbucket-solid" /></template>
