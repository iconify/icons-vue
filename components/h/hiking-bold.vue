<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxi8hkb5i.css';
import '../../css/h/hvxzctpfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxi8hkb5i"/><path clip-rule="evenodd" class="hvxzctpfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hiking-bold" /></template>
