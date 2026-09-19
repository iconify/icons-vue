<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="satq-_bxj"/><path class="d0juhqbry"/><path class="ohw4gibov"/><path class="gf75ejkvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-sao-tome-and-principe" /></template>
<style>
.d0juhqbry {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M1 23h63v18H1z");
}

.gf75ejkvo {
  fill: var(--svg-color--25333a, #25333a);
  d: path("m40.681 30.25l-4.371.01l-1.342-4.412l-1.346 4.412l-4.362-.01l3.536 2.68l-1.366 4.38l3.543-2.719l3.547 2.719l-1.37-4.38zm17.132 0l-4.363.01l-1.35-4.412l-1.345 4.412l-4.365-.01l3.539 2.68l-1.366 4.38l3.537-2.719l3.551 2.719l-1.371-4.38z");
}

.ohw4gibov {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M22.416 32L4.486 11.5C1.513 13.407 0 16.942 0 21v22c0 3.883 1.385 7.289 4.11 9.246l18.344-20.219z");
}

.satq-_bxj {
  fill: var(--svg-color--3e9a00, #3e9a00);
  d: path("M15.75 39.016L4.121 52.238C5.656 53.345 7.609 54 10 54h44c6.627 0 10-4.925 10-11v-4zM54 10H10c-2.201 0-4.03.553-5.514 1.5L15.879 25h48.12v-4c0-6.075-3.373-11-10-11");
}

</style>
