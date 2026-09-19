<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ne4u3pz3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ne4u3pz3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-right-circle-fill" /></template>
