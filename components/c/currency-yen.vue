<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcapv9ssm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcapv9ssm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:currency-yen" /></template>
