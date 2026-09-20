<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":273};
const content = `<path class="skv37db7b"/><path class="t81lutb3j"/><path class="pmwmb8bbf"/><path class="ii9nhmh5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:kore" /></template>
<style>
.ii9nhmh5v {
  d: path("M193.33 239.545c-31.571 18.785-67.757 24.99-97.9 16.112l-60.214 17.632l6.224-56.236c-.35-.519-.694-1.04-1.031-1.563c-25.275-39.17-16.762-99.995 19.23-126.99c-9.55 41.614-8.103 85.773 20.15 117.953c28.087 31.99 65.979 43.376 113.542 33.092");
  fill: var(--svg-color--009cde, #009CDE);
}

.pmwmb8bbf {
  d: path("M22.861 199.117c-36.192-52.3-27.999-119.33 14.6-152.526c37.424-29.164 87.095-26.222 126.945 9.772c-42.17-6.676-83.573-2.633-113.74 27.76c-29.989 30.214-37.015 67.982-27.805 114.994");
  fill: var(--svg-color--ef3340, #EF3340);
}

.skv37db7b {
  d: path("M235.065 64.604c34.744 53.273 24.716 120.053-18.778 152.069c-38.21 28.125-95.885 25.379-128.367-13.767c41.972 7.829 85.208 5.441 116.198-24.114c30.806-29.38 38.865-66.941 30.947-114.188");
  fill: var(--svg-color--6cc24a, #6CC24A);
}

.t81lutb3j {
  d: path("M56.82 23.861c52.3-36.192 119.33-27.999 152.526 14.6c29.163 37.424 28.332 82.173-1.877 122.023c6.675-42.17-5.262-78.651-35.655-108.819C141.6 21.677 103.832 14.651 56.82 23.861");
  fill: var(--svg-color--a77bca, #A77BCA);
}

</style>
