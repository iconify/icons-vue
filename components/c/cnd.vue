<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzqt9rbax.css';
import '../../css/p/pm0grmbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zzqt9rbax"/><path class="pm0grmbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:cnd" /></template>
