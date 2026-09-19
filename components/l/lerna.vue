<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9cggyj4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p9cggyj4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:lerna" /></template>
