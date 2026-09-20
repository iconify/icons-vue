<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4nvolk3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="v4nvolk3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:call-transfer" /></template>
