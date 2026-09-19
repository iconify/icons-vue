<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt5nkhb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kt5nkhb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:claude" /></template>
