<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":296};
const content = `<path class="pw65b8bpj"/><path class="n1agmhbve"/><path class="r09bsekej"/><path class="utx684bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:chartjs" /></template>
<style>
.n1agmhbve {
  fill: var(--svg-color--ffce56, #ffce56);
  d: path("M248.572 146.426c-13.832-17.752-23.214-38.16-43.4-38.16c-35.72 0-26.32 58.271-65.798 58.271c-39.482 0-43.633-62.679-88.358-3.759c-14.252 18.774-25.723 39.707-34.734 59.515l111.812 64.549l120.478-69.551z");
}

.pw65b8bpj {
  fill: var(--svg-color--36a2eb, #36a2eb);
  d: path("M248.572 148.807c-41.32.811-32.713 26.969-61.833 33.584c-29.582 6.72-34.252-72.248-63.826-72.248c-29.579 0-36.13 76.709-73.166 129.37l-1.057 1.491l79.404 45.836l120.478-69.551z");
}

.r09bsekej {
  fill: var(--svg-color--fe6184, #fe6184);
  d: path("M7.613 170.564c13.555-37.538 19.405-67.94 45.283-67.94c39.478 0 48.875 110.908 82.718 99.625c33.838-11.278 30.077-71.432 82.719-71.432c10.02 0 20.25 6.138 30.241 16.067v70.405l-120.478 69.55L7.613 217.29z");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.utx684bng {
  fill: var(--svg-color--e7e9ed, #e7e9ed);
  d: path("M128 295.56L0 221.673V73.89L128 0l128 73.89v147.78zM15.039 212.99L128 278.2l112.961-65.21V82.572L128 17.362L15.039 82.572z");
}

</style>
