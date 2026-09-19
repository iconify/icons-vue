<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptdinhqmn.css';
import '../../css/m/m5swtfbed.css';
import '../../css/z/zyduq6bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ptdinhqmn"/><path class="m5swtfbed"/><path class="zyduq6bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-compose" /></template>
