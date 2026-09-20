<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gwu5y9wqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gwu5y9wqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:flag-solid" /></template>
