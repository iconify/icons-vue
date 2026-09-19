<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwooq4bpl.css';
import '../../css/z/zkjh13stl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nwooq4bpl"/><path class="zkjh13stl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:eye-slash-16-solid" /></template>
