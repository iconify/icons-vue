<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7s9cworz.css';
import '../../css/l/l6n8opbbo.css';
import '../../css/b/btotlsqon.css';
import '../../css/g/g5hek6cqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7s9cworz"/><path clip-rule="evenodd" class="l6n8opbbo"/><path class="btotlsqon"/><path class="g5hek6cqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-minimalistic-outline" /></template>
