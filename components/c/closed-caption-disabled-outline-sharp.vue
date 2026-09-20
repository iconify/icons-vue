<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r24q73b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:closed-caption-disabled-outline-sharp" /></template>
<style>
.r24q73b3b {
  fill: currentColor;
  d: path("m9.314 9.308l.884.884H7.577v3.616h2.615v-.577h.885v1.461H6.692V9.308zM7.817 5H20v12.183l-1-1V6H8.817zm9.49 8.23v1.232h-.028l-.885-.885h.029v-.346zm-.884-2.422v-.616h-2.615v.799l-.847-.847v-.836h4.347v1.5zm-5.534 1.502v-.006zM5.085 5.079l.92.921H5v12h11.579L1.887 3.308l.713-.714l19.223 19.223l-.713.714L17.579 19H4V5.079z");
}

</style>
