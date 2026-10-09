<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9wdjs-os.css';
import '../../css/k/kkcxbwb5w.css';
import '../../css/x/xwdhawfba.css';
import '../../css/h/hayl1lfmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f9wdjs-os"/><path class="kkcxbwb5w"/><path class="xwdhawfba"/><path class="hayl1lfmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:image-plus-20-bold" /></template>
