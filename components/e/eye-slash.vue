<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6apa6btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="n6apa6btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:eye-slash" /></template>
