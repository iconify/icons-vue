<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hef1qdbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hef1qdbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:down-circle-solid" /></template>
