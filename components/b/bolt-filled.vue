<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b0ca_zb6s.css';
import '../../css/g/gp21txb1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b0ca_zb6s"/><path clip-rule="evenodd" class="gp21txb1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bolt-filled" /></template>
