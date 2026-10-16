<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nmle-2ous.css';
import '../../css/y/yi354_nqc.css';
import '../../css/v/v7fhe39su.css';
import '../../css/y/yct5lw59k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="nmle-2ous"/><path class="yi354_nqc"/><path class="v7fhe39su"/><path class="yct5lw59k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:growth-20" /></template>
