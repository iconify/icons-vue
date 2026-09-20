<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":242};
const content = `<path class="iamb-7oaa"/><path class="uoftxr33t"/><path class="n08rndvzk"/><path class="oy5otvbxe"/><path class="kl4pt6ffh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:lit" /></template>
<style>
.iamb-7oaa {
  d: path("M475.256 93.967v34.696H512v18.793h-36.744v42.888c0 4.336.12 8.673.603 12.408c.964 6.385 4.819 12.65 10.12 15.059c6.866 3.132 11.685 2.53 26.021 2.048l-3.494 20.72c-.963.483-4.818.362-8.433.362c-8.433 0-40.237 3.012-46.742-29.756c-1.084-5.662-.843-11.445-.843-20.36v-43.128h-16.384l.24-19.155h16.144V93.967zm-62.283 34.575v110.23h-22.648v-110.23zm0-34.575v19.637h-22.89V93.967zM312.26 217.088h58.067l-21.685 21.685h-59.513V93.967h23.13z");
}

.kl4pt6ffh {
  fill: var(--svg-color--0ff, #0ff);
  d: path("M48.188 240.941v-96.376l48.188 48.188z");
}

.n08rndvzk {
  fill: var(--svg-color--283198, #283198);
  d: path("M96.376 192.753V96.376l48.189-48.188v96.377zm-96.376 0l48.188 48.188l6.929-45.63l-6.929-50.746l-28.267 17.851z");
}

.oy5otvbxe {
  fill: var(--svg-color--324fff, #324fff);
  d: path("M48.188 144.565V48.188L96.376 0v96.376zm96.377 96.376v-96.376l48.188-48.189v96.377zM0 192.753V96.376l48.188 48.189z");
}

.uoftxr33t {
  fill: var(--svg-color--00e8ff, #00e8ff);
  d: path("m48.188 144.565l19.521-33.677l28.787-14.392l48.169 48.169l8.156 46.497l-8.256 49.779l-48.189-48.188l-28.667-19.287z");
}

</style>
