<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txy8rw54j.css';
import '../../css/a/a9q9e7b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="txy8rw54j"/><path clip-rule="evenodd" class="a9q9e7b6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:calendar-no-access-solid" /></template>
