<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm3xmebmn.css';
import '../../css/g/gykrvcc7h.css';
import '../../css/u/uz7k7mbin.css';
import '../../css/b/b4wag86-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="qm3xmebmn"/><path class="gykrvcc7h"/><path class="uz7k7mbin"/><path class="b4wag86-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:insurance-twotone" /></template>
