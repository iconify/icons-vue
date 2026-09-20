<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pz0uj0bdt.css';
import '../../css/b/bn449xbii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz0uj0bdt"/><path class="bn449xbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:envelope-solid" /></template>
