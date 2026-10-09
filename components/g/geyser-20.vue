<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbjnu1baw.css';
import '../../css/b/bzz03rb9j.css';
import '../../css/g/gwv7mvsvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rbjnu1baw"/><path class="bzz03rb9j"/><path class="gwv7mvsvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:geyser-20" /></template>
