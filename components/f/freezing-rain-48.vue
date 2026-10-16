<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv91ufroz.css';
import '../../css/y/y4teju86f.css';
import '../../css/k/kmncaq-ru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kv91ufroz"/><path class="y4teju86f"/><path class="kmncaq-ru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:freezing-rain-48" /></template>
