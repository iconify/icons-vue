<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k65h5h91a.css';
import '../../css/d/dtgkx25td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k65h5h91a"/><path class="dtgkx25td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:bootstrapping" /></template>
