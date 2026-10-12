<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f9tkrk29k.css';
import '../../css/s/ssh18kvpm.css';
import '../../css/e/emg88iban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f9tkrk29k"/><path class="ssh18kvpm"/><path class="emg88iban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-x-duotone" /></template>
