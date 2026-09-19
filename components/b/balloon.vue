<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npgudrbvm.css';
import '../../css/s/sqx9578-o.css';
import '../../css/v/v1pzelk4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="npgudrbvm"/><path class="sqx9578-o"/><path class="v1pzelk4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:balloon" /></template>
