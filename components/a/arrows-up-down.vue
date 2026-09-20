<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-2g-uwgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="b-2g-uwgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:arrows-up-down" /></template>
