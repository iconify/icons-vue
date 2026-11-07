<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i4w_uybke.css';
import '../../css/a/apggtqbru.css';
import '../../css/g/giaponbgv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4w_uybke"/><path class="apggtqbru"/><path class="giaponbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:document-bold-duotone" /></template>
