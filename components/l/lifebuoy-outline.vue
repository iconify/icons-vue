<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebc1v__7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ebc1v__7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:lifebuoy-outline" /></template>
