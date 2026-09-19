<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2rc8bbax.css';
import '../../css/s/skkebdnpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":24};
const content = `<path class="z2rc8bbax"/><path class="skkebdnpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:holiday-village" /></template>
