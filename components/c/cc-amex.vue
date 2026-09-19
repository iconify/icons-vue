<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iagb11b3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="iagb11b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cc-amex" /></template>
