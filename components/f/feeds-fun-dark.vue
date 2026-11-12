<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxthvrb8t.css';
import '../../css/i/im-69xmjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dxthvrb8t"/><path class="im-69xmjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:feeds-fun-dark" /></template>
