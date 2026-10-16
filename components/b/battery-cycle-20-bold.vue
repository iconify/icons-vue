<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9xn_wl3y.css';
import '../../css/z/z7jcrbb9a.css';
import '../../css/z/zf9c-5_5w.css';
import '../../css/l/l87qshb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l9xn_wl3y"/><path class="z7jcrbb9a"/><path class="zf9c-5_5w"/><path class="l87qshb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-cycle-20-bold" /></template>
