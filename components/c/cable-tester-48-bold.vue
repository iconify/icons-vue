<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pifoudbdm.css';
import '../../css/v/vuyyv1qil.css';
import '../../css/v/vr8_6rk9r.css';
import '../../css/l/lggnzh-ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pifoudbdm"/><path class="vuyyv1qil"/><path class="vr8_6rk9r"/><path class="lggnzh-ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-tester-48-bold" /></template>
