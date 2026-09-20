<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdtai9brg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="bdtai9brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:luggage-trolley" /></template>
