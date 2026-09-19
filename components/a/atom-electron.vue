<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn-6xjbzp.css';
import '../../css/b/b84mesy0c.css';
import '../../css/j/jb-_-ybkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="dn-6xjbzp"/><path class="b84mesy0c"/><circle class="jb-_-ybkr"><animateMotion dur="2s" path="M14.75 14.1471C12.2277 15.6034 9.69019 16.4332 7.6407 16.6145C5.54599 16.7998 4.15833 16.3018 3.62324 15.375C3.08815 14.4482 3.35067 12.9974 4.55852 11.276C5.74031 9.59178 7.72768 7.80915 10.25 6.35289C12.7723 4.89662 15.3098 4.06682 17.3593 3.88549C19.454 3.70016 20.8417 4.1982 21.3768 5.125C21.9118 6.0518 21.6493 7.50256 20.4415 9.22397C19.2597 10.9082 17.2723 12.6909 14.75 14.1471Z" repeatCount="indefinite"/></circle>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:atom-electron" /></template>
