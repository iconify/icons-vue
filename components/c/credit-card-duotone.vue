<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6k6c5bss.css';
import '../../css/s/sa4jv-b7i.css';
import '../../css/q/qq3vuebmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6k6c5bss"/><circle class="sa4jv-b7i"/><path class="qq3vuebmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:credit-card-duotone" /></template>
