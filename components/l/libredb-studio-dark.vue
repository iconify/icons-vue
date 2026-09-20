<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uezwkhbui.css';
import '../../css/k/k-_y3hhqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uezwkhbui"/><path class="k-_y3hhqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:libredb-studio-dark" /></template>
