<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz_cz4bbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sz_cz4bbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:down-filled" /></template>
