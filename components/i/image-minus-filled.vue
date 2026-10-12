<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9e3_dbsz.css';
import '../../css/b/b31iesblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k9e3_dbsz"/><path class="b31iesblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:image-minus-filled" /></template>
