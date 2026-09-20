<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stk0jfp5a.css';
import '../../css/s/sjc8stbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":196,"height":256};
const content = `<path class="stk0jfp5a"/><path class="sjc8stbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:afordin-light" /></template>
