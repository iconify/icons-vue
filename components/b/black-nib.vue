<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="o1lw164rg"/><path class="ui853wa6y"/><path class="n7ebfu4ns"/><path class="kn1qym11k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:black-nib" /></template>
<style>
.kn1qym11k {
  fill: var(--svg-color--66757f, #66757f);
  d: path("m8.225 16.56l8.334-8.335l2.124 2.125l-8.333 8.334z");
}

.n7ebfu4ns {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M26.643 18.309L9.44 1.105L1.107 9.44l17.202 17.202a2.95 2.95 0 0 0 4.168 0l4.166-4.168a2.945 2.945 0 0 0 0-4.165");
}

.o1lw164rg {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M31.986 32.729a2 2 0 0 1-.987.271a2 2 0 1 1 2-2c0 .361-.104.695-.271.987l3.146 3.146L34.999 28l-9-7l-5 5l7 9l7.134.876z");
}

.ui853wa6y {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M13.643 5.308a2.946 2.946 0 0 1 0 4.167l-4.167 4.168a2.95 2.95 0 0 1-4.167 0L1.141 9.475a2.95 2.95 0 0 1 0-4.167l4.167-4.167a2.946 2.946 0 0 1 4.167 0z");
}

</style>
