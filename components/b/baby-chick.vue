<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gd-7l3sog"/><path class="r8e5ewz8l"/><path class="ymyorbn9t"/><path class="fkany9b1s"/><path class="qw935zvkd"/><path class="f7dhz-boj"/><path class="bvbtc3b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:baby-chick" /></template>
<style>
.bvbtc3b5s {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M24.339 23.24c0 3.286-2.192 5.942-4.899 5.942s-4.907-2.657-4.907-5.942c0-3.279 2.2-5.945 4.907-5.945s4.899 2.666 4.899 5.945");
}

.f7dhz-boj {
  fill: var(--svg-color--f4f5f5, #f4f5f5);
  d: path("M26.824 22.894c0 4.949-3.308 8.956-7.385 8.956c-4.081 0-7.393-4.01-7.393-8.956c0-4.948 3.312-8.954 7.393-8.954c4.078 0 7.385 4.01 7.385 8.954");
}

.fkany9b1s {
  fill: var(--svg-color--f05a2a, #f05a2a);
  d: path("M20.334 39.854c0-5.548 5.226-1.356 11.664-1.356c6.446 0 11.667-4.191 11.667 1.356c0 5.558-5.226 16.06-11.667 16.06c-6.438 0-11.664-10.502-11.664-16.06");
}

.gd-7l3sog {
  fill: var(--svg-color--f7ec35, #f7ec35);
  d: path("M1.729 42.04c0 12.137 13.545 21.963 30.27 21.963c16.724 0 30.27-9.826 30.27-21.963C62.269 29.92 48.725 0 31.999 0C15.272 0 1.729 29.912 1.729 42.04");
}

.qw935zvkd {
  fill: var(--svg-color--f79420, #f79420);
  d: path("M20.338 36.07c0-5.548 5.226-1.362 11.667-1.362s11.664-4.186 11.664 1.362c0 5.556-5.226 16.05-11.664 16.05c-6.442 0-11.667-10.499-11.667-16.05");
}

.r8e5ewz8l {
  fill: var(--svg-color--f4f5f5, #f4f5f5);
  d: path("M52.42 23.516c0 4.95-3.308 8.958-7.385 8.958c-4.082 0-7.394-4.01-7.394-8.958c0-4.945 3.312-8.954 7.394-8.954c4.077 0 7.385 4.01 7.385 8.954");
}

.ymyorbn9t {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M49.934 23.861c0 3.283-2.191 5.942-4.898 5.942c-2.708 0-4.907-2.659-4.907-5.942c0-3.28 2.199-5.947 4.907-5.947c2.706 0 4.898 2.667 4.898 5.947");
}

</style>
