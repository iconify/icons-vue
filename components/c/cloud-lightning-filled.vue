<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2k9crezi.css';
import '../../css/k/koc75zbyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d2k9crezi"/><path class="koc75zbyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cloud-lightning-filled" /></template>
