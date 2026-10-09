<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaei814vi.css';
import '../../css/x/xwqlmeb2f.css';
import '../../css/i/i10hk57ox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kaei814vi"/><path class="xwqlmeb2f"/><path class="i10hk57ox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-charger-home-48" /></template>
