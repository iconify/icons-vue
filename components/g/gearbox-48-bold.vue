<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gg03hcbot.css';
import '../../css/y/ybe7dm20u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gg03hcbot"/><path class="ybe7dm20u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gearbox-48-bold" /></template>
