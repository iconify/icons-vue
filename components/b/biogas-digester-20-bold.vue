<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b98g_82cf.css';
import '../../css/w/wg1zusbqd.css';
import '../../css/h/hko9syb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b98g_82cf"/><path class="wg1zusbqd"/><path class="hko9syb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:biogas-digester-20-bold" /></template>
