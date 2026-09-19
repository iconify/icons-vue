<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v5d4tfb5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="v5d4tfb5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:exclamationmark-octagon" /></template>
