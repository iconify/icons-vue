<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k1gqgyb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":455,"height":512};
const content = `<path class="k1gqgyb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:c" /></template>
